<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nabfewbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nabfewbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:align-justify-solid" /></template>
