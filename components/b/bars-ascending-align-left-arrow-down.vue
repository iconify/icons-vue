<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb775zgkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gb775zgkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars-ascending-align-left-arrow-down" /></template>
