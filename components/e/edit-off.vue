<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb8-3blsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hb8-3blsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:edit-off" /></template>
