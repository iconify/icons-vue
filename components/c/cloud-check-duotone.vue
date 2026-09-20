<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8lvwbib.css';
import '../../css/e/ef5ug6bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8lvwbib"/><path class="ef5ug6bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-check-duotone" /></template>
