<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccemtwbeg.css';
import '../../css/w/w3qhuhbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ccemtwbeg"/><path class="w3qhuhbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:high-voltage" /></template>
