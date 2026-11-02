<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avekk7_9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avekk7_9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hdmi-port-fill" /></template>
