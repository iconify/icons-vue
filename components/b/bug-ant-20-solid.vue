<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnzewhb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nnzewhb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bug-ant-20-solid" /></template>
