<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kov7snrof.css';
import '../../css/l/l5zpj0bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kov7snrof"/><path class="l5zpj0bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-changesets-open" /></template>
