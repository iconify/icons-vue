<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewb4zlb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewb4zlb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:edit-off-filled" /></template>
