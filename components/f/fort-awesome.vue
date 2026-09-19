<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r43xucbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r43xucbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:fort-awesome" /></template>
