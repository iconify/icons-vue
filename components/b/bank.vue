<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiqt2mbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wiqt2mbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bank" /></template>
