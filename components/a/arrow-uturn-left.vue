<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1zwhfbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n1zwhfbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-uturn-left" /></template>
