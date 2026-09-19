<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieo439fpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieo439fpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:biceps" /></template>
