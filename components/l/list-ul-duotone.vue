<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjx1jgzfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjx1jgzfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:list-ul-duotone" /></template>
