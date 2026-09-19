<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-dn_rb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-dn_rb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:highlights" /></template>
