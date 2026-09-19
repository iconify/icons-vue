<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg41evs9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wg41evs9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:dots-circle-horizontal" /></template>
