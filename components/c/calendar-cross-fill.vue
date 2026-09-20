<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7mukz4un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7mukz4un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-cross-fill" /></template>
