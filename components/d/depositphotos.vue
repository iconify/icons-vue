<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytzj93bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytzj93bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:depositphotos" /></template>
