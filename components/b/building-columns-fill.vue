<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aer2r279m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="aer2r279m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:building-columns-fill" /></template>
