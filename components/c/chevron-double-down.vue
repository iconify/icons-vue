<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8byqac1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8byqac1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:chevron-double-down" /></template>
