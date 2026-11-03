<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs1a2jbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs1a2jbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bluetooth-solid" /></template>
