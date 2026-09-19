<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srrc7m5nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="srrc7m5nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:commentround" /></template>
