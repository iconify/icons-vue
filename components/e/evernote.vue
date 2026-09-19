<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7p1x9bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":617,"height":740};
const content = `<path class="a7p1x9bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:evernote" /></template>
