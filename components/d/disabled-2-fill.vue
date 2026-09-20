<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm723rb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm723rb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-2-fill" /></template>
