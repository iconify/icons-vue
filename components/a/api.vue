<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4dq40b1b.css';
import '../../css/k/k_2ois9bt.css';
import '../../css/w/w5fsu1wxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4dq40b1b"/><path class="k_2ois9bt"/><path class="w5fsu1wxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:api" /></template>
