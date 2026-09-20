<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw9f3qb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw9f3qb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gny" /></template>
