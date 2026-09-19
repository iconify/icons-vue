<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wacjiqbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wacjiqbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-6-circle-fill" /></template>
