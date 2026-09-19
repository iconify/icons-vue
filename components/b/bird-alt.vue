<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq5zwab2c.css';
import '../../css/d/d1uus8zrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq5zwab2c"/><path class="d1uus8zrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bird-alt" /></template>
