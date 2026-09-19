<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfp51pbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1025};
const content = `<path class="hfp51pbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:evernote" /></template>
