<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp8skrysh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp8skrysh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:code-pull-request-outline" /></template>
