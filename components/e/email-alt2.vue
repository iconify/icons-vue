<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6mibqsee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q6mibqsee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:email-alt2" /></template>
