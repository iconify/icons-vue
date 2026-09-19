<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkd76en_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lkd76en_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:json" /></template>
