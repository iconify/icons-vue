<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3bcjsagj.css';
import '../../css/g/gx0yaobvf.css';
import '../../css/p/p6j-kgamt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3bcjsagj"/><path class="gx0yaobvf"/><path class="p6j-kgamt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:first-aid-48" /></template>
