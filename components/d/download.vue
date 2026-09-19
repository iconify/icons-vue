<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcj7q3bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hcj7q3bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:download" /></template>
