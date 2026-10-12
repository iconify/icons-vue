<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udxw1ou3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="udxw1ou3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folders-stroke-20" /></template>
