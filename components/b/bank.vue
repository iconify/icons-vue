<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6ztzx0-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w6ztzx0-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bank" /></template>
