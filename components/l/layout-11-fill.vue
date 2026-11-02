<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8tagfb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8tagfb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-11-fill" /></template>
