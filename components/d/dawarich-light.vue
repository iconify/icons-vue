<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdtzqfxwt.css';
import '../../css/j/jk619tm-u.css';
import '../../css/w/wm7ofvb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdtzqfxwt"/><path class="jk619tm-u"/><path class="wm7ofvb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dawarich-light" /></template>
