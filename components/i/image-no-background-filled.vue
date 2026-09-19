<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ax2rb3c.css';
import '../../css/z/zsbatf1yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ax2rb3c"/><path class="zsbatf1yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-no-background-filled" /></template>
