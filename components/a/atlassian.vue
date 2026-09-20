<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi6eslbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi6eslbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:atlassian" /></template>
