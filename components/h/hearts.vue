<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_3u8ean.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="aa_3u8ean"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hearts" /></template>
