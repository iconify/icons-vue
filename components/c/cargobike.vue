<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3zj0bcws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g3zj0bcws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike" /></template>
