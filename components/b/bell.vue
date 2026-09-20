<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyabaibxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kyabaibxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:bell" /></template>
