<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/polvqg_iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="polvqg_iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-user" /></template>
