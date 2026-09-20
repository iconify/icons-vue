<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dks-8vbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dks-8vbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:anonymous-off" /></template>
