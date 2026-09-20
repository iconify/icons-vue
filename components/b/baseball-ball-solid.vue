<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s23gm2xlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s23gm2xlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:baseball-ball-solid" /></template>
