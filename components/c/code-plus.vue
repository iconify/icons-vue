<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6q3gcbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6q3gcbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:code-plus" /></template>
