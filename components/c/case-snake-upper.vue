<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5le0mbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5le0mbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:case-snake-upper" /></template>
