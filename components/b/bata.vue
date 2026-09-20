<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djn3ugbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djn3ugbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bata" /></template>
