<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-igur5jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-igur5jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-edit-location" /></template>
