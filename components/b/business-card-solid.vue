<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmf4h2brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pmf4h2brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:business-card-solid" /></template>
