<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsijkbbus.css';
import '../../css/m/m3bl0tblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hsijkbbus"/><path class="m3bl0tblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-mjml-open" /></template>
