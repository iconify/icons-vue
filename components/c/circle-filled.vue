<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5-j6_bca.css';
import '../../css/s/svdy80z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="d5-j6_bca"/><path class="svdy80z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circle-filled" /></template>
