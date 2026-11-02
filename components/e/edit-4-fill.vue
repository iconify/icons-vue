<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_a_vsb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_a_vsb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-4-fill" /></template>
