<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af04s8mfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="af04s8mfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lifeempty" /></template>
