<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihf3etbjh.css';
import '../../css/p/ph2qz-bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihf3etbjh"/><path class="ph2qz-bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:alarm" /></template>
