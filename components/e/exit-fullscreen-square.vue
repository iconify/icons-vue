<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9mmgjblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9mmgjblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:exit-fullscreen-square" /></template>
