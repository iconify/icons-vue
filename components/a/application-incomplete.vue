<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gki61o8vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gki61o8vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:application-incomplete" /></template>
