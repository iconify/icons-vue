<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx1la0w2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx1la0w2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-incompatible" /></template>
