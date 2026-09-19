<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0txjs4ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0txjs4ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:logout" /></template>
