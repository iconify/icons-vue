<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkmy9uvwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pkmy9uvwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-2-outline" /></template>
