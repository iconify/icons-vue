<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn-sj6b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn-sj6b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-five" /></template>
