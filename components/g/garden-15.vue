<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdegzkbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gdegzkbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:garden-15" /></template>
