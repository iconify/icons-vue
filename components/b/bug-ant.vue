<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnnt3_9du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnnt3_9du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bug-ant" /></template>
