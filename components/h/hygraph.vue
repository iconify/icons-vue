<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrnudiz8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":55};
const content = `<path class="rrnudiz8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hygraph" /></template>
