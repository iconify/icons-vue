<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhp0hry1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vhp0hry1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:corner-up-left-duotone" /></template>
