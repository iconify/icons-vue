<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-hd3s68u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-hd3s68u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:checkmark-done-circle" /></template>
