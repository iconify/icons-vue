<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk-75mhpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zk-75mhpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:champagne-party-alcohol-solid" /></template>
