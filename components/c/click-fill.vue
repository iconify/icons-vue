<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oissyjbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oissyjbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:click-fill" /></template>
