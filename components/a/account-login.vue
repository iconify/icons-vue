<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs9dl9bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vs9dl9bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:account-login" /></template>
