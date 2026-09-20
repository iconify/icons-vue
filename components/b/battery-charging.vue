<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko1yq89rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1yq89rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-charging" /></template>
