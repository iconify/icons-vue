<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-sv5cbsg.css';
import '../../css/e/ejoji3b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-sv5cbsg"/><path class="ejoji3b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:houses-filled" /></template>
