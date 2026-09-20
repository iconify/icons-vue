<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5wn1cbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u5wn1cbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-tongue-solid" /></template>
