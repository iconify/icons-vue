<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5t5jabpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t5t5jabpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:genie" /></template>
