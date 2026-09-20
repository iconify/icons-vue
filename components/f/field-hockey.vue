<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsx3hltkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hsx3hltkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:field-hockey" /></template>
