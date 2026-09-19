<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4hrb0bhl.css';
import '../../css/e/ekp95gbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="o4hrb0bhl"/><path class="ekp95gbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:laboratory" /></template>
