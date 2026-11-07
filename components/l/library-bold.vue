<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3_gtob6t.css';
import '../../css/p/p9-9dkipc.css';
import '../../css/u/u4839bbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="p9-9dkipc"/><path clip-rule="evenodd" class="u4839bbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:library-bold" /></template>
