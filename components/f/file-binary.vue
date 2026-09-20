<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foer5hbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="foer5hbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-binary" /></template>
