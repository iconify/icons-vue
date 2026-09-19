<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzmen5ibp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzmen5ibp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:airplane-alt-01-filled" /></template>
