<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs929z2uj.css';
import '../../css/k/krr-sfb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bs929z2uj"/><path class="krr-sfb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-dump-open" /></template>
