<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q17hgibso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":999,"height":1000};
const content = `<path class="q17hgibso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-wink" /></template>
