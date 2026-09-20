<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lywcgt26c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lywcgt26c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hash" /></template>
