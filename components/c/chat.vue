<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qskswgxvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qskswgxvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:chat" /></template>
