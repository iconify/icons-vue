<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omy7fbu9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omy7fbu9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-down-right" /></template>
