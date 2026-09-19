<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd5_3bctn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sd5_3bctn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hexagon" /></template>
