<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz_w1whsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz_w1whsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dental-mirror" /></template>
