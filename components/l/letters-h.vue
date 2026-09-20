<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5tf-399p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5tf-399p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-h" /></template>
