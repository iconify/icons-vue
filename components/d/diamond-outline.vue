<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_4yq_bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_4yq_bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:diamond-outline" /></template>
