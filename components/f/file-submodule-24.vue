<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5eg7w4dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5eg7w4dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-submodule-24" /></template>
