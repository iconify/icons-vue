<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpub25bol.css';
import '../../css/j/jqfr0dnja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpub25bol"/><path class="jqfr0dnja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-trash-open" /></template>
