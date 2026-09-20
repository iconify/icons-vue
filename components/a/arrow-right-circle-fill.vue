<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm7fgh3tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm7fgh3tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-circle-fill" /></template>
