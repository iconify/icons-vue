<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_a_bjblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_a_bjblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-network-filled" /></template>
