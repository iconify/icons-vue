<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7shhm5zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q7shhm5zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-badge-20-solid" /></template>
