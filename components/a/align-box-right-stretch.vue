<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv7socc2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv7socc2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-right-stretch" /></template>
