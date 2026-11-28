<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lncx4q9ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lncx4q9ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:circle-3" /></template>
