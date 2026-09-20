<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1yujle_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1yujle_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gameloft" /></template>
