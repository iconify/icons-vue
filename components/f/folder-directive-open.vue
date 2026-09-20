<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpub25bol.css';
import '../../css/q/q-anz_blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpub25bol"/><path class="q-anz_blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-directive-open" /></template>
