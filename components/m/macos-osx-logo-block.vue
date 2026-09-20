<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx_7q067g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fx_7q067g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:macos-osx-logo-block" /></template>
