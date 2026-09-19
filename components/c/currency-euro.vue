<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keu35jbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keu35jbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:currency-euro" /></template>
