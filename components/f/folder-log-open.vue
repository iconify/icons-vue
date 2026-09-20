<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9_amsz7a.css';
import '../../css/t/t7parlbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h9_amsz7a"/><path class="t7parlbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-log-open" /></template>
