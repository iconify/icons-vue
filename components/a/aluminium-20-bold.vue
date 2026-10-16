<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpwlrrj0w.css';
import '../../css/b/bcnnsuiaf.css';
import '../../css/r/rjummxbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jpwlrrj0w"/><path class="bcnnsuiaf"/><path class="rjummxbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aluminium-20-bold" /></template>
