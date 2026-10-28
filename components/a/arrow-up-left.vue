<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bio0il38c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bio0il38c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-left" /></template>
