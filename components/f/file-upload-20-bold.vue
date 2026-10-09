<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8im5qk_h.css';
import '../../css/i/igzi4qboy.css';
import '../../css/v/vqn5vt5cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="igzi4qboy"/><path class="vqn5vt5cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-upload-20-bold" /></template>
