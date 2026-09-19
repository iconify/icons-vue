<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcgdaipoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcgdaipoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-list-filled" /></template>
