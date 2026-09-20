<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b67ohqy9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b67ohqy9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:check-circle-one-solid" /></template>
