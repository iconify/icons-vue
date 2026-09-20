<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzq7745mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzq7745mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-up-large-duotone" /></template>
