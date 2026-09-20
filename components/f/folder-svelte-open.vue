<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsijkbbus.css';
import '../../css/a/ads0gkbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hsijkbbus"/><path class="ads0gkbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-svelte-open" /></template>
