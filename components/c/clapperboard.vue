<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvowzcblg.css';
import '../../css/l/ljexf9bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer kvowzcblg"/><path class="duoicon-primary-layer ljexf9bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:clapperboard" /></template>
