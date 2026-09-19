<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svmeeohaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svmeeohaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h1" /></template>
