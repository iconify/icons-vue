<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txd2f3f6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txd2f3f6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:angles-right" /></template>
