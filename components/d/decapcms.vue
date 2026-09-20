<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv4ubdb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv4ubdb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:decapcms" /></template>
