<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvepz4bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvepz4bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-audio-doorbell" /></template>
