<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7539_bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7539_bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-4-sharp" /></template>
