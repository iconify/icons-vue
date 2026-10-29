<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwd0xy2he.css';
import '../../css/u/u8e_e0bbm.css';
import '../../css/i/i_7whfb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwd0xy2he"/><path class="u8e_e0bbm"/><path class="i_7whfb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:folder-open" /></template>
