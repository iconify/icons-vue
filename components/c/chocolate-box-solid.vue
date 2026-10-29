<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6hmb2j6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6hmb2j6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chocolate-box-solid" /></template>
