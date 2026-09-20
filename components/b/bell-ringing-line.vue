<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atbu4hsrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atbu4hsrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-ringing-line" /></template>
