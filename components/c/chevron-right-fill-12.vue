<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0tnk7uws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c0tnk7uws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-right-fill-12" /></template>
