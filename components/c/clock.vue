<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpwwd192v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wpwwd192v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:clock" /></template>
