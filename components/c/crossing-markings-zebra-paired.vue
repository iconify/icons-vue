<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6brsoc_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t6brsoc_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crossing-markings-zebra-paired" /></template>
