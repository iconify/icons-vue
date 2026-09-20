<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz8zv6d6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz8zv6d6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-left-duotone" /></template>
