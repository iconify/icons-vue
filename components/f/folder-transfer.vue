<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieuaz4n3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieuaz4n3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-transfer" /></template>
