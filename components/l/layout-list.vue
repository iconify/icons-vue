<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrpocrbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrpocrbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:layout-list" /></template>
