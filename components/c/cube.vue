<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzqqk7bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzqqk7bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cube" /></template>
