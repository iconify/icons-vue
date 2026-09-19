<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po7dnf-xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po7dnf-xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-euro" /></template>
