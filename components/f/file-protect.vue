<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj03nbfem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fj03nbfem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-protect" /></template>
