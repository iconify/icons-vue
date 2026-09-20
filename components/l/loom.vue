<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p49jc6i4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p49jc6i4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:loom" /></template>
