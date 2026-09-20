<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkg7e-bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nkg7e-bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:layers" /></template>
