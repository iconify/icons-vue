<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk30anbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="qk30anbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:address-card" /></template>
