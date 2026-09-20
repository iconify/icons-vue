<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohmcow45c.css';
import '../../css/e/emp3rxbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmcow45c"/><path class="emp3rxbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hmnd" /></template>
