<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-v_1rjed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-v_1rjed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:align-justify" /></template>
