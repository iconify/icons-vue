<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb3of5z4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb3of5z4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dashboard-3-fill" /></template>
