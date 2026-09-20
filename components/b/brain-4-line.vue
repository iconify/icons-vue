<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4n3vub7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4n3vub7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-4-line" /></template>
