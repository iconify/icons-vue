<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0oo4lbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z0oo4lbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:invoice-outline" /></template>
