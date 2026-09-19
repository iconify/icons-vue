<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytw07_b-i.css';
import '../../css/v/vh7f-ub8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ytw07_b-i"/><path class="vh7f-ub8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bikini" /></template>
