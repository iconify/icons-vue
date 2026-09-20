<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv0ph5bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv0ph5bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:black-hole3" /></template>
