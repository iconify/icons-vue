<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_c93jb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_c93jb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:access-point-plus" /></template>
