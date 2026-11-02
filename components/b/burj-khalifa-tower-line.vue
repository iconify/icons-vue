<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec0xa6blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec0xa6blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:burj-khalifa-tower-line" /></template>
