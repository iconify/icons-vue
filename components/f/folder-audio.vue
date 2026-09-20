<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95-ijf-n.css';
import '../../css/c/chh58g-wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="chh58g-wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-audio" /></template>
