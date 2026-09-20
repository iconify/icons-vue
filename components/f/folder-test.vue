<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbbjl8juq.css';
import '../../css/b/b5v4ogcih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wbbjl8juq"/><path class="b5v4ogcih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-test" /></template>
