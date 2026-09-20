<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q87qb_bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q87qb_bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:autoit" /></template>
