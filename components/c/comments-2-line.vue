<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odfhc8bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odfhc8bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comments-2-line" /></template>
