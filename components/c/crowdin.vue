<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqgyks5ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqgyks5ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:crowdin" /></template>
