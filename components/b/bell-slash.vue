<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzze97bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tzze97bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bell-slash" /></template>
