<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw_z6bmih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw_z6bmih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:backbonejs-logo-block" /></template>
