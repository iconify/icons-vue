<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2mwc6apt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="v2mwc6apt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:joint" /></template>
