<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/synrjp3rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="synrjp3rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:folder-delete" /></template>
