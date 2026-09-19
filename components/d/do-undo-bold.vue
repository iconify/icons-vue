<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xum33lbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xum33lbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-undo-bold" /></template>
