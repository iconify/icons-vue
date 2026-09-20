<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjc94rm5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjc94rm5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:command-fill" /></template>
