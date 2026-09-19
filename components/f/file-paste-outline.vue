<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egt-gsfjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egt-gsfjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-paste-outline" /></template>
