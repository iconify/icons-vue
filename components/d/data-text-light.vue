<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxzum9b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxzum9b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-text-light" /></template>
