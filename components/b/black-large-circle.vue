<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1kn8_3bk.css';
import '../../css/k/kbay0kr8o.css';
import '../../css/t/tlh0720xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="f1kn8_3bk"/><path class="kbay0kr8o"/><path class="tlh0720xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-large-circle" /></template>
