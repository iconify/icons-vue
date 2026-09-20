<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvto7gvzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvto7gvzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-check-fill" /></template>
