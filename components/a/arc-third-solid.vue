<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o17z0g3wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o17z0g3wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arc-third-solid" /></template>
