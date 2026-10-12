<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gih_8gbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gih_8gbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:highlighter-filled" /></template>
