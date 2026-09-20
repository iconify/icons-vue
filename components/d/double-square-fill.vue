<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc4xlwb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc4xlwb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:double-square-fill" /></template>
