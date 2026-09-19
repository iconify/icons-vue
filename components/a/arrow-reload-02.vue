<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whpitybyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whpitybyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-reload-02" /></template>
