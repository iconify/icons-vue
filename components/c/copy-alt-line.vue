<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba495nb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba495nb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:copy-alt-line" /></template>
