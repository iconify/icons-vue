<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knnax3buu.css';
import '../../css/v/vbuatlb1w.css';
import '../../css/j/jymfo0b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knnax3buu"/><path class="vbuatlb1w"/><path class="jymfo0b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:batch-job" /></template>
