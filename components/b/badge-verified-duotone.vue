<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k889x9ems.css';
import '../../css/y/ye4h3ob-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k889x9ems"/><path class="ye4h3ob-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:badge-verified-duotone" /></template>
