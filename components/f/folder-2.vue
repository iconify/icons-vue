<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf50w7myg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hf50w7myg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-2" /></template>
