<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j80ujrauk.css';
import '../../css/q/qsvb7nb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j80ujrauk"/><path class="qsvb7nb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:building-3-filled" /></template>
