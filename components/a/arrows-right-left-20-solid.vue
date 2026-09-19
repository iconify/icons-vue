<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz0diwtcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yz0diwtcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-right-left-20-solid" /></template>
