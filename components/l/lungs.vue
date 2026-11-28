<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oov89x65i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oov89x65i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lungs" /></template>
