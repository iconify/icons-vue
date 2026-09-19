<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhm5-k6is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yhm5-k6is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:chevron-down" /></template>
