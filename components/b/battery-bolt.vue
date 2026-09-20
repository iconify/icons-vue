<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkh4xzpqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkh4xzpqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:battery-bolt" /></template>
