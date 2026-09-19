<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4s39lk4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s4s39lk4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:dollar" /></template>
