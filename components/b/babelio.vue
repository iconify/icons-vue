<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkma7xxvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkma7xxvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:babelio" /></template>
