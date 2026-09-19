<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wygg5fb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wygg5fb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-black-suit-circled-small" /></template>
