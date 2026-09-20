<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v14bsqblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v14bsqblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:eye-off" /></template>
