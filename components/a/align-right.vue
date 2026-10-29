<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4rqfpek.css';
import '../../css/r/rzrmuq82c.css';
import '../../css/c/c1uaxoita.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="rzrmuq82c"/><path class="c1uaxoita"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:align-right" /></template>
