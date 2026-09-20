<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt4wtjaxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt4wtjaxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-left-large-duotone" /></template>
