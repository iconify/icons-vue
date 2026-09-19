<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3_pnwttb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":959};
const content = `<path class="f3_pnwttb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dice" /></template>
