<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ot5pd2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1ot5pd2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:caret-right-outline" /></template>
