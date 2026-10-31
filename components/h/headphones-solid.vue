<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6i2-jkox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6i2-jkox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-solid" /></template>
