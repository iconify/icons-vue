<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ony59q43f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ony59q43f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:calendar-fill" /></template>
