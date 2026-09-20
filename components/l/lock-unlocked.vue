<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li7mzybab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="li7mzybab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:lock-unlocked" /></template>
