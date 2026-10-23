<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1k9vcchc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1k9vcchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brain-off" /></template>
