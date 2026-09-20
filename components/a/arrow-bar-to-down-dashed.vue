<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhha36vhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhha36vhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-bar-to-down-dashed" /></template>
