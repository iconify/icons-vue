<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csq89hwxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="csq89hwxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:lightbulb" /></template>
