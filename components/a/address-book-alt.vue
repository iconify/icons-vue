<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/andt_0b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="andt_0b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:address-book-alt" /></template>
