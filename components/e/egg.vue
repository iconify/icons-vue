<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsfwnr_ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bsfwnr_ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:egg" /></template>
