<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqon457lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqon457lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dumbbell-solid" /></template>
