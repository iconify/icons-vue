<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5y77qbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v5y77qbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:coupling-facility-encryption" /></template>
