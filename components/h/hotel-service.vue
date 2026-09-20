<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb8m35buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb8m35buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hotel-service" /></template>
