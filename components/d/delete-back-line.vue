<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz7vauv-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz7vauv-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-back-line" /></template>
