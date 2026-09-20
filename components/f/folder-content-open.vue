<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3gib6vnb.css';
import '../../css/j/jh04-5upe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v3gib6vnb"/><path class="jh04-5upe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-content-open" /></template>
