<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdv0xacjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fdv0xacjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-white-suit-small" /></template>
