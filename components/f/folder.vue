<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av5ai0bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av5ai0bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:folder" /></template>
