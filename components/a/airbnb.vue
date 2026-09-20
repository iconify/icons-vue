<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2u9n_9xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i2u9n_9xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:airbnb" /></template>
