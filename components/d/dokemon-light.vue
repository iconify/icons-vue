<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h23lf5ovw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h23lf5ovw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dokemon-light" /></template>
