<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzirv-blp.css';
import '../../css/a/anwa3301w.css';
import '../../css/k/k_8lvdbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lzirv-blp"/><path class="anwa3301w"/><path clip-rule="evenodd" class="k_8lvdbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:audio-interface-16" /></template>
