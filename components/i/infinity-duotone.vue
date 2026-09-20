<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dor5b2bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dor5b2bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:infinity-duotone" /></template>
