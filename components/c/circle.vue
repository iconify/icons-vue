<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr3jxxbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="jr3jxxbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:circle" /></template>
