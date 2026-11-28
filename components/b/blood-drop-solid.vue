<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gibrudeyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gibrudeyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:blood-drop-solid" /></template>
