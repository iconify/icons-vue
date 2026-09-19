<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku-wjcb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ku-wjcb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:circle-dashed" /></template>
