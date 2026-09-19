<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9eql3aen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9eql3aen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:alarm-bell" /></template>
