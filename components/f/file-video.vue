<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlm1i_1oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlm1i_1oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-video" /></template>
