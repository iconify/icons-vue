<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa2b7z3tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa2b7z3tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-right-outline" /></template>
