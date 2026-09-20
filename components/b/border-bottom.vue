<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rum1edbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rum1edbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:border-bottom" /></template>
