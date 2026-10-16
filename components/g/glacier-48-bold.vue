<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkjsbignm.css';
import '../../css/f/fkpmaxbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dkjsbignm"/><path class="fkpmaxbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glacier-48-bold" /></template>
