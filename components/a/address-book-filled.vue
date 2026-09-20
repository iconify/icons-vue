<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbv8r5b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbv8r5b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:address-book-filled" /></template>
