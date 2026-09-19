<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2wj9ob8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2wj9ob8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-star-filled" /></template>
