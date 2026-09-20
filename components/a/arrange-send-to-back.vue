<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al428908v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al428908v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrange-send-to-back" /></template>
