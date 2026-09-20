<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwdwx0byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwdwx0byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-dashed" /></template>
