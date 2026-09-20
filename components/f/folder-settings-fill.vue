<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utw1xcbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utw1xcbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-settings-fill" /></template>
