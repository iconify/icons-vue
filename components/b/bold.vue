<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihbn3ee0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ihbn3ee0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:bold" /></template>
