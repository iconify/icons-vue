<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz0ro8h5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qz0ro8h5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:gratipay" /></template>
