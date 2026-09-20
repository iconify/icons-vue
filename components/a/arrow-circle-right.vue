<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvkz5rbsj.css';
import '../../css/h/hzy4kud9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvkz5rbsj"/><path class="hzy4kud9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-right" /></template>
