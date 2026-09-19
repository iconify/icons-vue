<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y87cecb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y87cecb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:download-option" /></template>
