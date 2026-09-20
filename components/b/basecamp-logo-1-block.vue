<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt2-f3eym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bt2-f3eym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:basecamp-logo-1-block" /></template>
