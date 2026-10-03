<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5eetpnom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5eetpnom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dishwasher-rinse-aid" /></template>
