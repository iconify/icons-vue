<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwx5wubgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwx5wubgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:eye-snake" /></template>
