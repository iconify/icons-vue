<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa8tgxnep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa8tgxnep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-fill" /></template>
