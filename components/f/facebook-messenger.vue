<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fckdgqt-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fckdgqt-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:facebook-messenger" /></template>
