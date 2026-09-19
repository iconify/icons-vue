<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt_urbb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt_urbb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-angled-rain-zap" /></template>
