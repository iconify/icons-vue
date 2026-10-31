<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eptx6fbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eptx6fbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:facebook-fill-round" /></template>
