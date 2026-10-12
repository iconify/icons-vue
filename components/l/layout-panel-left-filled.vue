<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkj6lmbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj6lmbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-panel-left-filled" /></template>
