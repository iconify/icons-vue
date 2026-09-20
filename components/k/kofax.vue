<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq6a8za2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq6a8za2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kofax" /></template>
