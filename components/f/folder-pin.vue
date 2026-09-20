<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnw4ovbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnw4ovbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-pin" /></template>
