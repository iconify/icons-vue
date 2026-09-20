<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhvz2l3_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhvz2l3_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:console" /></template>
