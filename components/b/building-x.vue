<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asl790y9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asl790y9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:building-x" /></template>
