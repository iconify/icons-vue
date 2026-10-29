<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewjvinb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewjvinb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:leaf-solid" /></template>
