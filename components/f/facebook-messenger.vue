<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnb9i2bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wnb9i2bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:facebook-messenger" /></template>
