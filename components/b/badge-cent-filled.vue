<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0oed5ccq.css';
import '../../css/m/mkm-s0byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0oed5ccq"/><path clip-rule="evenodd" class="mkm-s0byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-cent-filled" /></template>
