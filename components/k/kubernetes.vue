<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb50vv9xt.css';
import '../../css/d/ds9388b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb50vv9xt"/><path class="ds9388b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:kubernetes" /></template>
