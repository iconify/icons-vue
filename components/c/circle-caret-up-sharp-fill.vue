<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrljmcked.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jrljmcked"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-up-sharp-fill" /></template>
