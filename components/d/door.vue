<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgbdwlrnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgbdwlrnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:door" /></template>
