<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_821ibzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i_821ibzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kjell-company-dark" /></template>
