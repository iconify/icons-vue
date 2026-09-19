<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uags2ccqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uags2ccqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:hand" /></template>
