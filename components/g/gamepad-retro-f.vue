<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8si76bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-6};
const content = `<path class="b8si76bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:gamepad-retro-f" /></template>
