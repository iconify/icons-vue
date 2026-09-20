<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecmj4ybyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecmj4ybyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:delete-2-bold" /></template>
