<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guzljmb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1792};
const content = `<path class="guzljmb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:eercast" /></template>
