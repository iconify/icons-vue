<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf6nudbzg.css';
import '../../css/f/frp2_fb2i.css';
import '../../css/e/e_5k39kyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":74,"height":24};
const content = `<path class="xf6nudbzg"/><path class="frp2_fb2i"/><path class="e_5k39kyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:logo-github-24" /></template>
