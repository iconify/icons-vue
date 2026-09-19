<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ril1flb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="ril1flb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:circle-fill" /></template>
