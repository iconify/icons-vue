<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9lfmybtd.css';
import '../../css/g/g6owz749s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9lfmybtd"/><path class="g6owz749s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-checkbox-square" /></template>
