<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmx63kvih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmx63kvih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-left-s" /></template>
