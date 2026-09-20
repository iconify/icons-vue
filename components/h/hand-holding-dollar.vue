<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z80t8obne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z80t8obne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:hand-holding-dollar" /></template>
