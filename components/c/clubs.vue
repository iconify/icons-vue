<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8fsvbcnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j8fsvbcnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:clubs" /></template>
