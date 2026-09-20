<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efbq6sbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efbq6sbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:book-marked" /></template>
