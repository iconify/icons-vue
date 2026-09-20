<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9cyzoooz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9cyzoooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:logseq" /></template>
