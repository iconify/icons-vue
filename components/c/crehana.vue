<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhhled0dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhhled0dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:crehana" /></template>
