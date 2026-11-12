<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmeqb77ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmeqb77ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dartboard" /></template>
