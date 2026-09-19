<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmq74bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcmq74bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:link-slash" /></template>
