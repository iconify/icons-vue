<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozmf5ipva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozmf5ipva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-pull-request-fill" /></template>
