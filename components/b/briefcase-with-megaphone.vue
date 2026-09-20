<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezsnwlscl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ezsnwlscl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-megaphone" /></template>
