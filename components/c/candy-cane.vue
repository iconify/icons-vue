<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg69lwbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg69lwbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:candy-cane" /></template>
