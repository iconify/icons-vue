<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiaq2lk7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiaq2lk7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-off" /></template>
