<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3hr03bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r3hr03bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-play" /></template>
