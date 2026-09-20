<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olbbfmh5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="olbbfmh5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hippo-solid" /></template>
