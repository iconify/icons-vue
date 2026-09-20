<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py41x_zcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py41x_zcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:drag-indicator-alt-duotone" /></template>
