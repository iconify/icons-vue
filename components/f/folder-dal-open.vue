<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpub25bol.css';
import '../../css/b/bngdwyyjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpub25bol"/><path class="bngdwyyjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-dal-open" /></template>
