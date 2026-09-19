<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf11o55rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf11o55rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-filled" /></template>
