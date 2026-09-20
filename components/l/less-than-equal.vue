<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezp0t7b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ezp0t7b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:less-than-equal" /></template>
