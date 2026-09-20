<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5obxuowy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5obxuowy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:globe-light" /></template>
