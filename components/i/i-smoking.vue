<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f635f9k-l.css';
import '../../css/b/bx7cagbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f635f9k-l"/><path class="bx7cagbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-smoking" /></template>
