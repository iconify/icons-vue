<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm0n2921s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm0n2921s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:blocks" /></template>
