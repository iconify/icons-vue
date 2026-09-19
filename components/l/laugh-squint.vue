<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik69wfwmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ik69wfwmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:laugh-squint" /></template>
