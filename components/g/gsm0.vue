<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sajs9zlog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sajs9zlog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gsm0" /></template>
