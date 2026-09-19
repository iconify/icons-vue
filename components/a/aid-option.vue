<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw8xh9zyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw8xh9zyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:aid-option" /></template>
