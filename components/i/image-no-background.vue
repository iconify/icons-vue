<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozmn8obvd.css';
import '../../css/z/zsbatf1yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozmn8obvd"/><path class="zsbatf1yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-no-background" /></template>
