<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqg8gvnrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqg8gvnrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:365-data-science" /></template>
