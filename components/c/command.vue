<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtexfebwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtexfebwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:command" /></template>
