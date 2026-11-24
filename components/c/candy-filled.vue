<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn_2kjoxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn_2kjoxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:candy-filled" /></template>
