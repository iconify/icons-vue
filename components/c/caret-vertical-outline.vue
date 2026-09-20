<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-b-cfejk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y-b-cfejk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:caret-vertical-outline" /></template>
