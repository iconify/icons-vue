<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu9rvubvf.css';
import '../../css/q/qauntjblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qu9rvubvf"/><path class="qauntjblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-drive-48-bold" /></template>
