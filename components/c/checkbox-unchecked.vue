<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p77veefer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p77veefer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:checkbox-unchecked" /></template>
