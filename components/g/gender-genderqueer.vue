<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p22cx9bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p22cx9bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-genderqueer" /></template>
