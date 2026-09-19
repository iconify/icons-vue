<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5usxdbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5usxdbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-circle-right" /></template>
