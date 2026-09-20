<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip9gr5baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip9gr5baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:air-humidifier" /></template>
