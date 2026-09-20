<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzp5midtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzp5midtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:comment" /></template>
