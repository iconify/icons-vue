<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcx3dab_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcx3dab_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cmdx" /></template>
