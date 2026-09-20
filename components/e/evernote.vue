<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl1fxiopl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl1fxiopl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:evernote" /></template>
