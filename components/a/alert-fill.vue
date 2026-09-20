<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brq9xm1sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brq9xm1sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-fill" /></template>
