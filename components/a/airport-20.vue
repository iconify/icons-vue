<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulf186bsh.css';
import '../../css/a/adm80pb1z.css';
import '../../css/f/f958kxxgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ulf186bsh"/><path class="adm80pb1z"/><path class="f958kxxgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airport-20" /></template>
