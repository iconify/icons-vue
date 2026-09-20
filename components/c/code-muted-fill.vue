<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgkj1ktcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgkj1ktcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:code-muted-fill" /></template>
