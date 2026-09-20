<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6k2gnciq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6k2gnciq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:amplifier" /></template>
