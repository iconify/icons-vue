<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obuk6_0gn.css';
import '../../css/a/azolbb4yn.css';
import '../../css/x/xxqak_76w.css';
import '../../css/r/rlavracrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="obuk6_0gn"/><path class="azolbb4yn"/><path class="xxqak_76w"/><path class="rlavracrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:firebase" /></template>
