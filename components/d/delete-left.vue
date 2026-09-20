<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyed1cbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyed1cbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:delete-left" /></template>
