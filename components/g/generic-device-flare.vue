<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oumarsd0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oumarsd0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-flare" /></template>
