<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpn7v4c7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpn7v4c7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:dots-horizontal" /></template>
