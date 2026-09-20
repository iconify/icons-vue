<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl8e5fbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl8e5fbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:list-numbers" /></template>
