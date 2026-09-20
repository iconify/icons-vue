<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j744k2xay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j744k2xay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cube" /></template>
