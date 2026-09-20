<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ug5rbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ug5rbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:globe-solid" /></template>
