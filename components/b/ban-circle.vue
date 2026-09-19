<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd55nxa0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cd55nxa0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:ban-circle" /></template>
