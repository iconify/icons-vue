<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj90n0u7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj90n0u7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lock-open" /></template>
