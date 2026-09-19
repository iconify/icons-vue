<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8nocibwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v8nocibwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:clothes-briefs" /></template>
