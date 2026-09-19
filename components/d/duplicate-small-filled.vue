<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4qeqybtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h4qeqybtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:duplicate-small-filled" /></template>
