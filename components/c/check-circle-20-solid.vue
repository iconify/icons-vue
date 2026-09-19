<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq7us0bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wq7us0bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-circle-20-solid" /></template>
