<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj6z6-b0q.css';
import '../../css/p/plsjqqb0l.css';
import '../../css/u/ubakjmb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj6z6-b0q"/><path class="plsjqqb0l"/><path clip-rule="evenodd" class="ubakjmb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-new-outline" /></template>
