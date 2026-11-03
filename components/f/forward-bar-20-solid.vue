<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dohn-wkdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dohn-wkdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:forward-bar-20-solid" /></template>
