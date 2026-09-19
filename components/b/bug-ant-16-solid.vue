<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sey0_cb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sey0_cb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bug-ant-16-solid" /></template>
