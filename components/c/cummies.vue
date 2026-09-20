<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgl_jgbvu.css';
import '../../css/k/k_3-ad-xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgl_jgbvu"/><path clip-rule="evenodd" class="k_3-ad-xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cummies" /></template>
