<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtlmueb0q.css';
import '../../css/f/fckebnbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtlmueb0q"/><path clip-rule="evenodd" class="fckebnbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cws" /></template>
