<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htfk-0bug.css';
import '../../css/u/u_em3xrxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htfk-0bug"/><path class="u_em3xrxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bluetooth" /></template>
