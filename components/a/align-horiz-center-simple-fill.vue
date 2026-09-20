<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw0com05s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw0com05s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-horiz-center-simple-fill" /></template>
