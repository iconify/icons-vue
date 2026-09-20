<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjs0mbcre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yjs0mbcre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:chevron-left" /></template>
