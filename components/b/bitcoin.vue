<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cisxu6win.css';
import '../../css/j/jub3nhbzk.css';
import '../../css/m/mx3d42bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cisxu6win"/><path class="jub3nhbzk"/><path class="mx3d42bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:bitcoin" /></template>
