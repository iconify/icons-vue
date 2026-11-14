<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owfbccc9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owfbccc9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-circle" /></template>
