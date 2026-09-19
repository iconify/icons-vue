<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykdahce2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ykdahce2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-triangle-left-fill" /></template>
