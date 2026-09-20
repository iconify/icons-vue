<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdhyr6bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdhyr6bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kyve" /></template>
