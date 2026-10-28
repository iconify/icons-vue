<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiowh3tts.css';
import '../../css/m/mujo0i2yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fiowh3tts"/><path class="mujo0i2yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows-forge" /></template>
