<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge-jeq6zd.css';
import '../../css/m/mexy6lbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ge-jeq6zd"/><path class="mexy6lbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gradle-open" /></template>
