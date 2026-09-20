<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5sqdxj-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5sqdxj-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-left-sharp-fill" /></template>
