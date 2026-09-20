<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slxt4ccor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slxt4ccor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:awesomelists" /></template>
