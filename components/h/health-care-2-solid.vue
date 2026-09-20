<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfv8tcc4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sfv8tcc4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:health-care-2-solid" /></template>
