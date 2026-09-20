<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5ykt5bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ykt5bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:beef" /></template>
