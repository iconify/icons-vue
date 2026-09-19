<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvhey3wrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvhey3wrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-0306m-24px" /></template>
