<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k34qf5lmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k34qf5lmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-down-left" /></template>
