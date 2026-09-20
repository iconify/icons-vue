<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpvnfjbpj.css';
import '../../css/a/a5arprq4h.css';
import '../../css/s/s88afubvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpvnfjbpj"/><path class="a5arprq4h"/><path class="s88afubvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:content-write" /></template>
