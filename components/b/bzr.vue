<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxd3y1b3a.css';
import '../../css/r/rtb6i2lma.css';
import '../../css/i/i6hc7lykz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxd3y1b3a"/><path class="rtb6i2lma"/><path class="i6hc7lykz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bzr" /></template>
