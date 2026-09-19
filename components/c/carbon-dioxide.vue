<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gna6b-1ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gna6b-1ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:carbon-dioxide" /></template>
