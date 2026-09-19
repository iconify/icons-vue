<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5lpkiu3h.css';
import '../../css/e/euvix8w7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5lpkiu3h"/><path class="euvix8w7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:lock" /></template>
