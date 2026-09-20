<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai4xf_p-i.css';
import '../../css/u/u-gxd5_sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai4xf_p-i"/><path class="u-gxd5_sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fps" /></template>
