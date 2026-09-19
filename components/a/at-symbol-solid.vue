<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2vky6jpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2vky6jpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:at-symbol-solid" /></template>
