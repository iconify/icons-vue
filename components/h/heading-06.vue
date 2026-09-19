<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7iybb6bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7iybb6bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading-06" /></template>
