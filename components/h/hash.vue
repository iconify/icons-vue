<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6fc4610v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6fc4610v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hash" /></template>
