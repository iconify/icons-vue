<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufb_vyhbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufb_vyhbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ear-outline-24px" /></template>
