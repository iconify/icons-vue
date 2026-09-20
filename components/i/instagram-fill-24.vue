<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueg7wcbbp.css';
import '../../css/c/coghm8bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueg7wcbbp"/><path clip-rule="evenodd" class="coghm8bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:instagram-fill-24" /></template>
