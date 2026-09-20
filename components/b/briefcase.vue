<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g67t8mbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g67t8mbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase" /></template>
