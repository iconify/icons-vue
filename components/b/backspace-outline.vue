<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb-qqv6dc.css';
import '../../css/j/j_2v-fbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb-qqv6dc"/><path clip-rule="evenodd" class="j_2v-fbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:backspace-outline" /></template>
