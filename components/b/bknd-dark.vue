<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pivbyhbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pivbyhbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bknd-dark" /></template>
