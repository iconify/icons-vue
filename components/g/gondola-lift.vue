<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gahb4hlyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gahb4hlyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:gondola-lift" /></template>
