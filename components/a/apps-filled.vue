<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxlj-rh_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlj-rh_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:apps-filled" /></template>
