<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffr2t8xmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ffr2t8xmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heavy-dollar-sign-small" /></template>
