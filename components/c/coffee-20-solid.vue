<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1zthtgtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t1zthtgtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:coffee-20-solid" /></template>
