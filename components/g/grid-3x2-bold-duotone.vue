<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2-x-cbeh.css';
import '../../css/f/fhhc7bnyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="fhhc7bnyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x2-bold-duotone" /></template>
