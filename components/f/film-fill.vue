<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apf31ib4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apf31ib4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-fill" /></template>
