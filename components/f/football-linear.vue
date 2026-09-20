<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkw00u83z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkw00u83z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:football-linear" /></template>
