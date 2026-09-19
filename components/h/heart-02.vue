<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4dxw5t5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dxw5t5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heart-02" /></template>
