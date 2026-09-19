<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_u3aceh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_u3aceh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-go-back" /></template>
