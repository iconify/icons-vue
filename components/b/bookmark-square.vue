<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk94esn1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk94esn1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bookmark-square" /></template>
