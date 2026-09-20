<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmdn5gl4d.css';
import '../../css/f/fglfh0u3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmdn5gl4d"/><path class="fglfh0u3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bug-filled" /></template>
