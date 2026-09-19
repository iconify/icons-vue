<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-xii3aka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="s-xii3aka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flashplayer" /></template>
