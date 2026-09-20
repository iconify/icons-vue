<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgqaonbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqaonbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hiking-fill" /></template>
