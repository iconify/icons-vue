<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqienwbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqienwbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:asterisk" /></template>
