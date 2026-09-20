<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3p4ryo0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3p4ryo0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-left-line" /></template>
