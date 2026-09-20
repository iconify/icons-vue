<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq-5qrh1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rq-5qrh1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-coffee-shop" /></template>
