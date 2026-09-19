<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izpldp4wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="izpldp4wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:instagram" /></template>
