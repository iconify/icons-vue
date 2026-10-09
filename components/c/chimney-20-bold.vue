<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nujs77b5j.css';
import '../../css/h/hw94v6bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nujs77b5j"/><path class="hw94v6bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chimney-20-bold" /></template>
