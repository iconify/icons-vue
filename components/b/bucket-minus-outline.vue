<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah61s_nqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah61s_nqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bucket-minus-outline" /></template>
