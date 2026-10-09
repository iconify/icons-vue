<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4fy6acsx.css';
import '../../css/b/bu7pjbvso.css';
import '../../css/h/h9uc7tbsz.css';
import '../../css/g/gj478sbzc.css';
import '../../css/b/b8z332bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i4fy6acsx"/><path class="bu7pjbvso"/><path class="h9uc7tbsz"/><path class="gj478sbzc"/><path class="b8z332bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charging-hub-48" /></template>
