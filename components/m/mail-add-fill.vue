<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy8gchbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy8gchbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-add-fill" /></template>
