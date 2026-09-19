<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhvihacbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhvihacbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-close-circle" /></template>
