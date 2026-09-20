<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt73p7fso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt73p7fso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:crown-solid" /></template>
