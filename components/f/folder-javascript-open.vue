<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8qgey2bj.css';
import '../../css/g/gurxminzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b8qgey2bj"/><path class="gurxminzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-javascript-open" /></template>
