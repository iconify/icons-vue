<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1jpej9ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1jpej9ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hard-drive-2-line" /></template>
