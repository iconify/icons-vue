<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f20im6pef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f20im6pef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dummy-circle" /></template>
