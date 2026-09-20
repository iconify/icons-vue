<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj4ormahr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="tj4ormahr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:campsite-11" /></template>
