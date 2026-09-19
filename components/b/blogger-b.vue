<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4s9n5t8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s4s9n5t8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:blogger-b" /></template>
