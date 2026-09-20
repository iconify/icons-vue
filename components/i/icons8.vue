<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp0o-snjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp0o-snjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:icons8" /></template>
