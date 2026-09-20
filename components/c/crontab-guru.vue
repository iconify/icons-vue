<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftit3v5he.css';
import '../../css/f/ffalivcqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftit3v5he"/><circle class="ffalivcqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crontab-guru" /></template>
