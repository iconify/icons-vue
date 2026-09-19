<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfibukysa.css';
import '../../css/e/ei2sh0bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lfibukysa"/><path class="ei2sh0bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:desk-adjustable" /></template>
