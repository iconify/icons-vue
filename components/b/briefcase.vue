<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1s7p1btp.css';
import '../../css/b/bkbgdy_cy.css';
import '../../css/u/uv5airb2t.css';
import '../../css/x/xgvfbubrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1s7p1btp"/><path class="bkbgdy_cy"/><path class="uv5airb2t"/><path class="xgvfbubrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:briefcase" /></template>
