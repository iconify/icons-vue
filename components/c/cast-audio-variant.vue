<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0de14sug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0de14sug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cast-audio-variant" /></template>
