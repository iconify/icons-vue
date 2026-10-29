<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4rqfpek.css';
import '../../css/t/ts-4hsfbk.css';
import '../../css/m/mjnimo6uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="ts-4hsfbk"/><path class="mjnimo6uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:align-left" /></template>
