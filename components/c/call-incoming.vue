<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8iztebqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g8iztebqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:call-incoming" /></template>
