<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpbf5qups.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpbf5qups"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cloudron" /></template>
