<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud3_pd4ak.css';
import '../../css/r/rhohvnbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ud3_pd4ak"/><path class="rhohvnbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-job" /></template>
