<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ygwptdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ygwptdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:columns-3-solid" /></template>
