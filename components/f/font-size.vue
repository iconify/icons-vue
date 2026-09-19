<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltnl8vnnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ltnl8vnnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:font-size" /></template>
