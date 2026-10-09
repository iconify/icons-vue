<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh4nptbku.css';
import '../../css/t/ttzlj2nix.css';
import '../../css/z/zei7q3mej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rh4nptbku"/><path class="ttzlj2nix"/><path class="zei7q3mej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-exchanger-20" /></template>
