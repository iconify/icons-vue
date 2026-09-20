<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/actcpjbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="actcpjbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:creativetechnology" /></template>
