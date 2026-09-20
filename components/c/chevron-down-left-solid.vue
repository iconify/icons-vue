<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnl21hbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnl21hbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-left-solid" /></template>
