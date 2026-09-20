<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd5cf5bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd5cf5bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:carlsberg-group" /></template>
