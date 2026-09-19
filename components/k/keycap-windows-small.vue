<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8tuk2fcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o8tuk2fcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-windows-small" /></template>
