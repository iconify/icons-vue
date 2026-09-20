<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkz5kod0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkz5kod0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:json-alt-2-duotone" /></template>
