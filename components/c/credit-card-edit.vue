<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8s1zbbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e8s1zbbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-edit" /></template>
