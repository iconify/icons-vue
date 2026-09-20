<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if0m9_emw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if0m9_emw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ello-logo-solid" /></template>
