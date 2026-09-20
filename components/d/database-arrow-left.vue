<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy1qikb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy1qikb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-arrow-left" /></template>
