<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg5bzjj2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg5bzjj2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arcam" /></template>
