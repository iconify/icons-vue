<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chy9vjf-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chy9vjf-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emphasis-cn" /></template>
