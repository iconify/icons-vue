<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz5sdrwre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz5sdrwre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:channel-add" /></template>
