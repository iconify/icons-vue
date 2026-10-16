<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8xpsfbik.css';
import '../../css/y/yn9nkwljy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n8xpsfbik"/><path class="yn9nkwljy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-solar-48" /></template>
