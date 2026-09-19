<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nojt2sbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nojt2sbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-spellbook" /></template>
