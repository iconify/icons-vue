<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp0-z8bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp0-z8bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dmtr" /></template>
