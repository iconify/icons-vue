<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r83azcbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r83azcbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-justify-start-filled" /></template>
