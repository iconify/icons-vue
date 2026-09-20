<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f32-ot3jq.css';
import '../../css/g/gxy-e0m8d.css';
import '../../css/b/bc9znburg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f32-ot3jq"/><path class="gxy-e0m8d"/><path class="bc9znburg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vue-directives" /></template>
