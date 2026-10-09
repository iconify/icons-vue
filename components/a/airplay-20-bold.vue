<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix3svnbbt.css';
import '../../css/g/gj1g8xb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ix3svnbbt"/><path class="gj1g8xb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airplay-20-bold" /></template>
