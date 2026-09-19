<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajb4hcbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ajb4hcbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:credit-card" /></template>
