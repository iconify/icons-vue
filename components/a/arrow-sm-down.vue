<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/borxzzipv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="borxzzipv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-sm-down" /></template>
