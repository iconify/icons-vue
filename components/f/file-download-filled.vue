<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-g932nak.css';
import '../../css/p/pt1jbnbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-g932nak"/><path class="pt1jbnbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-download-filled" /></template>
