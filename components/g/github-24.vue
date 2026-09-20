<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd25lnj5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd25lnj5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:github-24" /></template>
