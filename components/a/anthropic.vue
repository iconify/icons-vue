<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znla7v_1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znla7v_1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:anthropic" /></template>
