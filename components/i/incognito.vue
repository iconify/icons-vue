<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn0_e_zgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rn0_e_zgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:incognito" /></template>
