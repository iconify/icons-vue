<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_o-8pb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_o-8pb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-plus" /></template>
