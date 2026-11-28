<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be-0ib18l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be-0ib18l primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bracket-right-duotone" /></template>
