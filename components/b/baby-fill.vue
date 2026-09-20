<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so95kxb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so95kxb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baby-fill" /></template>
