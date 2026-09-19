<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj5w2w0co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj5w2w0co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-circle-solid" /></template>
