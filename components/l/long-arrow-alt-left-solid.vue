<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcjsrx5uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vcjsrx5uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:long-arrow-alt-left-solid" /></template>
