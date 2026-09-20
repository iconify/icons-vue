<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwgshwb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwgshwb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dapr" /></template>
