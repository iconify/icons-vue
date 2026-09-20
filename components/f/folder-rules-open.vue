<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixetddbeg.css';
import '../../css/w/w_b6j-_2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ixetddbeg"/><path class="w_b6j-_2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-rules-open" /></template>
