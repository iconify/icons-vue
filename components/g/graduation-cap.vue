<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-as5n38j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-as5n38j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:graduation-cap" /></template>
