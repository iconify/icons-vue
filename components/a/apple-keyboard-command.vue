<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iawrygbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iawrygbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-keyboard-command" /></template>
