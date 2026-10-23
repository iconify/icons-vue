<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-axo7bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-axo7bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:candy-off" /></template>
