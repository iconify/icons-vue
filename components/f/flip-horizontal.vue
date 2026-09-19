<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw14af3mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iw14af3mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flip-horizontal" /></template>
