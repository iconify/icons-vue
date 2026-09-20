<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjsjj9bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjsjj9bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dialpad" /></template>
