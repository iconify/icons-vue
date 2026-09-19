<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qns24b55v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qns24b55v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building-hospital-filled" /></template>
