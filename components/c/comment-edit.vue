<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lob1607iw.css';
import '../../css/j/j1kdqfrps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lob1607iw"/><path class="j1kdqfrps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:comment-edit" /></template>
