<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqn6nsbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqn6nsbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-charging" /></template>
