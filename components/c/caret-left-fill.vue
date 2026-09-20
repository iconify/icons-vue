<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f93xtsbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f93xtsbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:caret-left-fill" /></template>
