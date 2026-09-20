<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul96qtblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul96qtblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:canary" /></template>
