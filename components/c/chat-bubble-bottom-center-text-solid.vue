<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz_vtj53w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tz_vtj53w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center-text-solid" /></template>
