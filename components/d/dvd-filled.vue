<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs3tcib1t.css';
import '../../css/e/e8yz86-ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3tcib1t"/><path class="e8yz86-ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dvd-filled" /></template>
