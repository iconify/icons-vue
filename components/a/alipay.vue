<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9oho0b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x9oho0b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:alipay" /></template>
