<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0lbe88nw.css';
import '../../css/f/f_tab8g_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0lbe88nw"/><path clip-rule="evenodd" class="f_tab8g_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-plus-outline" /></template>
