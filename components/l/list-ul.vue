<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daui_jbia.css';
import '../../css/f/f7gi_3bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daui_jbia"/><path class="f7gi_3bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:list-ul" /></template>
