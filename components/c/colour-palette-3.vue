<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uynwflb5l.css';
import '../../css/f/f-ypa7iae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="uynwflb5l"/><path clip-rule="evenodd" class="f-ypa7iae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:colour-palette-3" /></template>
