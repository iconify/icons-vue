<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlok4jstc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlok4jstc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:help-square-filled" /></template>
