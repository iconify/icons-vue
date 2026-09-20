<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjrb-gbdh.css';
import '../../css/r/rkdm0ob1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjrb-gbdh"/><path class="rkdm0ob1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-boat-success" /></template>
