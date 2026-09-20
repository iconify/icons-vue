<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aunnx6las.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aunnx6las"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chield-check-fill" /></template>
