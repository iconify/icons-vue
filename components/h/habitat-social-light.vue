<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x04di0hqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x04di0hqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:habitat-social-light" /></template>
