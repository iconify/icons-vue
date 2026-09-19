<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz-rw6wtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz-rw6wtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fingerprint-phone" /></template>
