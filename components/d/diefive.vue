<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-rfr86ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":959};
const content = `<path class="s-rfr86ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:diefive" /></template>
