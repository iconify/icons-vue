<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfu8axb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfu8axb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:insights" /></template>
