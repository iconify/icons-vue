<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o48nptb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o48nptb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-grin-tongue-squint" /></template>
