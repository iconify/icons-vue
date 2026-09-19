<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku3wncb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ku3wncb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lightning-1-fill" /></template>
