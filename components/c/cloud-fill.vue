<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2c5zztnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i2c5zztnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-fill" /></template>
