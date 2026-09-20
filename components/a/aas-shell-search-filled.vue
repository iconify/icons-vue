<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feh3568qk.css';
import '../../css/s/se175u0vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feh3568qk"/><path clip-rule="evenodd" class="se175u0vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-search-filled" /></template>
