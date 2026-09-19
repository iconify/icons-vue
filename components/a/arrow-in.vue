<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okfctab9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":384};
const content = `<path class="okfctab9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:arrow-in" /></template>
