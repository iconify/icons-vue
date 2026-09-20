<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t73q5-q3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t73q5-q3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bug" /></template>
