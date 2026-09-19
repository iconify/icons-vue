<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo6s7v_7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="eo6s7v_7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:less" /></template>
