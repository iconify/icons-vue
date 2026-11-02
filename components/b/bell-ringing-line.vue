<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7cb2zbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7cb2zbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-ringing-line" /></template>
