<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo1ap9bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1ap9bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:google-drive-light" /></template>
