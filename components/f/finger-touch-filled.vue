<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plnf21w4w.css';
import '../../css/f/fowt9fbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plnf21w4w"/><path class="fowt9fbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-touch-filled" /></template>
