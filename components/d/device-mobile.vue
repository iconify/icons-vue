<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk-w9rb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk-w9rb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:device-mobile" /></template>
