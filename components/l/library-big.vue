<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeeny6cmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeeny6cmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:library-big" /></template>
