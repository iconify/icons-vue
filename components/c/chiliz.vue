<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tewny_bsl.css';
import '../../css/i/ichklriki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tewny_bsl"/><path clip-rule="evenodd" class="ichklriki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:chiliz" /></template>
