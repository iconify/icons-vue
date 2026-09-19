<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw5x7wlrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw5x7wlrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:ban-outline" /></template>
