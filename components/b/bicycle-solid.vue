<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwg2an-cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xwg2an-cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bicycle-solid" /></template>
