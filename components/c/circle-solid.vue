<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtitn8o0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtitn8o0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:circle-solid" /></template>
