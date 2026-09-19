<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3dyj_nsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3dyj_nsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fog-filled" /></template>
