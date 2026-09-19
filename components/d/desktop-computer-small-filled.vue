<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izxbt9bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="izxbt9bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:desktop-computer-small-filled" /></template>
