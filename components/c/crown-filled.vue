<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqmbybb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqmbybb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crown-filled" /></template>
