<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zw34bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x6zw34bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-right-small-outline" /></template>
