<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8sacuuou.css';
import '../../css/y/yusbh7bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8sacuuou"/><path class="yusbh7bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-paypal" /></template>
