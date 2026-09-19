<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igm4--b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="igm4--b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:credit-card" /></template>
