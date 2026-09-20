<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olf_b7bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olf_b7bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heading-solid" /></template>
