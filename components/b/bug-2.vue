<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-evrg8nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-evrg8nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bug-2" /></template>
