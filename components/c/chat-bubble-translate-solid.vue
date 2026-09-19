<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phew_p5rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phew_p5rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-translate-solid" /></template>
