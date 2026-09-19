<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0zq4nbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e0zq4nbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-bangladeshi-solid" /></template>
