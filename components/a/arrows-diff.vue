<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqgowxbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqgowxbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-diff" /></template>
