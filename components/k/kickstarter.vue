<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc2dki62s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc2dki62s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kickstarter" /></template>
