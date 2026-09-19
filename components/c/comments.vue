<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjws7nb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="rjws7nb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:comments" /></template>
