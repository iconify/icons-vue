<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-4zo-uap.css';
import '../../css/g/gl-k21bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-4zo-uap"/><path class="gl-k21bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-migrations-open" /></template>
