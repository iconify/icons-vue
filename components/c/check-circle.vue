<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0bz8sb9m.css';
import '../../css/r/rs6irjb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0bz8sb9m"/><path class="rs6irjb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:check-circle" /></template>
