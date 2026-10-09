<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8im5qk_h.css';
import '../../css/i/igzi4qboy.css';
import '../../css/p/pwggbdcyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="igzi4qboy"/><path class="pwggbdcyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-download-20-bold" /></template>
