<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otue91qts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otue91qts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:baidu" /></template>
