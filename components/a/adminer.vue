<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-kgf2jpm.css';
import '../../css/k/kje3pp6ll.css';
import '../../css/g/gp-ljubwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v-kgf2jpm"/><path class="kje3pp6ll"/><path class="gp-ljubwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:adminer" /></template>
