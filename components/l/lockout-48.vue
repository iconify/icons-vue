<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a829lwbpl.css';
import '../../css/n/nk1pwkb6d.css';
import '../../css/h/haixszbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a829lwbpl"/><path class="nk1pwkb6d"/><path class="haixszbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockout-48" /></template>
