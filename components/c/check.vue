<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaim9281v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaim9281v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check" /></template>
