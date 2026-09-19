<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0w342ldx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0w342ldx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:discord-solid" /></template>
