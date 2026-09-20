<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6q3khb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6q3khb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-linkedin-filled" /></template>
