<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqjtt0biw.css';
import '../../css/a/a3yyyw2au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zqjtt0biw"/><path class="a3yyyw2au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:droplet-48" /></template>
