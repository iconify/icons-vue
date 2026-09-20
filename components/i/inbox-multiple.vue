<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbfh3yblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbfh3yblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inbox-multiple" /></template>
