<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp68ljb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lp68ljb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homer-light" /></template>
