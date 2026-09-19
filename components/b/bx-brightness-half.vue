<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvt8a1byh.css';
import '../../css/q/qfpw5-bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvt8a1byh"/><path class="qfpw5-bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-brightness-half" /></template>
