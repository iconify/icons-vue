<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls9339kws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls9339kws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-4" /></template>
