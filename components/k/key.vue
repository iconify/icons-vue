<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdvbt-kba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdvbt-kba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:key" /></template>
