<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iofeebenh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iofeebenh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:candy-cane" /></template>
