<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ium3vbbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ium3vbbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-dolphinscheduler" /></template>
