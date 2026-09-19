<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6_yl3b8x.css';
import '../../css/e/e8w1e_bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6_yl3b8x"/><path class="e8w1e_bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:envelope-open-solid" /></template>
