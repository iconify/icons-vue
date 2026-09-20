<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dep_0wujp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dep_0wujp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:chrysler" /></template>
