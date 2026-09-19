<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqgh9acwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqgh9acwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:language-solid" /></template>
