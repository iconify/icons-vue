<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty9awnngf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ty9awnngf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:book" /></template>
