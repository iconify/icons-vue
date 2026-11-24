<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weapb9upb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weapb9upb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:alarm-clock-off-filled" /></template>
