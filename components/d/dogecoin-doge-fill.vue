<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u36f9db9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u36f9db9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dogecoin-doge-fill" /></template>
