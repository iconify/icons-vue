<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orhr1cbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orhr1cbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:gift-top" /></template>
