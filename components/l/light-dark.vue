<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3ywpbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ob3ywpbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:light-dark" /></template>
