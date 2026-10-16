<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m21xs_4fm.css';
import '../../css/u/u3htxq4vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m21xs_4fm"/><path class="u3htxq4vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidifier-20" /></template>
