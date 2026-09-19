<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwi3tdbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwi3tdbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:link-05" /></template>
