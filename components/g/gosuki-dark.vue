<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bodxe5byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bodxe5byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gosuki-dark" /></template>
