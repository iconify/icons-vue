<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esr320baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esr320baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alist-light" /></template>
