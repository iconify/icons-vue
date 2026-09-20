<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqshe0eia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqshe0eia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:keyboard-alt" /></template>
