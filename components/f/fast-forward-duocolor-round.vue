<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aabr3imbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aabr3imbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-duocolor-round" /></template>
