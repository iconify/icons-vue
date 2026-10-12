<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tggzodb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tggzodb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-plus-filled" /></template>
