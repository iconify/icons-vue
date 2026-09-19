<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms1t--bpr.css';
import '../../css/h/h9o6htbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms1t--bpr"/><path class="h9o6htbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cool" /></template>
