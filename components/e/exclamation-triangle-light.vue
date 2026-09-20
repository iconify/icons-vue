<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv8-yz4el.css';
import '../../css/j/jvw8zwcpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8-yz4el"/><path clip-rule="evenodd" class="jvw8zwcpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-triangle-light" /></template>
