<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo53krbdf.css';
import '../../css/v/vf-n7zb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vo53krbdf"/><path class="vf-n7zb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-parking-20" /></template>
