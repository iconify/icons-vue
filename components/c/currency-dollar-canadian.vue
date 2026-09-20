<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odcedq8ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odcedq8ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dollar-canadian" /></template>
