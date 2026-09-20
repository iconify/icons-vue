<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj8p36bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj8p36bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flashlight" /></template>
