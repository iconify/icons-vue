<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhdu9cbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yhdu9cbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:baby-carriage" /></template>
