<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc_qa9b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc_qa9b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:insurance-hands-solid" /></template>
