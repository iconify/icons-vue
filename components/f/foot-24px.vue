<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9bv10guk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z9bv10guk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:foot-24px" /></template>
