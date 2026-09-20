<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2wul1yco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2wul1yco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-edit-filled" /></template>
