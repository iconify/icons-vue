<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp4c2mbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp4c2mbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-2-charge-fill" /></template>
