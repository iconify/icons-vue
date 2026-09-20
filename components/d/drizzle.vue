<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyn7ksb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyn7ksb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:drizzle" /></template>
