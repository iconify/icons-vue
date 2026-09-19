<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjmase5-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bjmase5-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cog-8-tooth" /></template>
