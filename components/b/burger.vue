<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndg-id0tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ndg-id0tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:burger" /></template>
