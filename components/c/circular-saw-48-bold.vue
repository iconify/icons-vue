<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bydf-9bza.css';
import '../../css/f/fe7lf8b9s.css';
import '../../css/e/e54qfbcyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bydf-9bza"/><path class="fe7lf8b9s"/><path class="e54qfbcyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circular-saw-48-bold" /></template>
