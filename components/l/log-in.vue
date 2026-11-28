<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6co-qb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6co-qb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:log-in" /></template>
