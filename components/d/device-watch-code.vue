<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjbw58qnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjbw58qnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-code" /></template>
