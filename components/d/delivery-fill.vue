<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kia8xccll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kia8xccll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:delivery-fill" /></template>
