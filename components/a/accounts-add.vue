<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uglkwz-2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="uglkwz-2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:accounts-add" /></template>
