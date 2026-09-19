<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eusk0o6ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":667,"height":688};
const content = `<path class="eusk0o6ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:eject" /></template>
