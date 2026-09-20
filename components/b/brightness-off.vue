<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5x23nlau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5x23nlau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brightness-off" /></template>
