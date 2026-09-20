<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95-ijf-n.css';
import '../../css/v/vriz6s5yi.css';
import '../../css/f/fzb--mpnf.css';
import '../../css/e/e20g_bbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><g class="vriz6s5yi"><path class="fzb--mpnf"/><path class="e20g_bbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-syntax" /></template>
