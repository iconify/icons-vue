<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6yz84b5g.css';
import '../../css/e/e2u938bif.css';
import '../../css/f/f1mld5bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6yz84b5g"/><path class="e2u938bif"/><path class="f1mld5bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hinge-48-bold" /></template>
