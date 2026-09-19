<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywz-nyv8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="ywz-nyv8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:account-o" /></template>
