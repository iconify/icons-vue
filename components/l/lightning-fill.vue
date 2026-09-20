<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le4jb36pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le4jb36pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lightning-fill" /></template>
