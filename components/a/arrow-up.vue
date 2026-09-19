<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxn4ublp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qlxn4ublp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-up" /></template>
