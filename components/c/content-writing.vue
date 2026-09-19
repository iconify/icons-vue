<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds2fz5baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds2fz5baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:content-writing" /></template>
