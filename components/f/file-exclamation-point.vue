<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7r6s5lmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7r6s5lmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-exclamation-point" /></template>
