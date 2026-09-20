<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt7ecmb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jt7ecmb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-edit-outline" /></template>
