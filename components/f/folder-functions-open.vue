<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9k8lxuwq.css';
import '../../css/g/g-7edib4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9k8lxuwq"/><path class="g-7edib4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-functions-open" /></template>
