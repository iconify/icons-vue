<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts3lanhek.css';
import '../../css/m/mlhjt3b1y.css';
import '../../css/m/m8vgwzb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ts3lanhek"/><path class="mlhjt3b1y"/><path class="m8vgwzb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dawarich" /></template>
