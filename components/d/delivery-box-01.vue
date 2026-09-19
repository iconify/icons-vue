<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe1l063ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe1l063ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delivery-box-01" /></template>
