<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abt6-fbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="abt6-fbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:battery-1" /></template>
