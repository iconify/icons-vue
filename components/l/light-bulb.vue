<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oho2e76vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oho2e76vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:light-bulb" /></template>
