<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd4zl3h1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd4zl3h1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-3-filled" /></template>
