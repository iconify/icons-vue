<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs5y9xb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs5y9xb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folders-check" /></template>
