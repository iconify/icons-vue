<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpyvibbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpyvibbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:globe-asia-australia" /></template>
