<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4ryjbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4ryjbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-right" /></template>
